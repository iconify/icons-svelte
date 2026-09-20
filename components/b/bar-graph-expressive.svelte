<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxr-fcc-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxr-fcc-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bar-graph-expressive" {...props}></Icon>
