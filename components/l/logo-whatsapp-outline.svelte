<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osbk2_69o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="osbk2_69o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-whatsapp-outline" {...props}></Icon>
