<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe_j1ac2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_j1ac2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ev-plug-ccs1" {...props}></Icon>
