<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrgayabaj.css';
import '../../css/a/amcez-bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jrgayabaj"/><path class="amcez-bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloud-upload-outline" {...props}></Icon>
