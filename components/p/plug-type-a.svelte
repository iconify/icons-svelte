<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz6f73b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz6f73b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:plug-type-a" {...props}></Icon>
