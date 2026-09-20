<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojo9uubfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojo9uubfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:photopea-dark" {...props}></Icon>
