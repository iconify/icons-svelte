<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpue87gvs.css';
import '../../css/i/iezp-tb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpue87gvs"/><path class="iezp-tb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cloud-warning-bold" {...props}></Icon>
