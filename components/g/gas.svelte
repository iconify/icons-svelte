<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgm17v0ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgm17v0ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:gas" {...props}></Icon>
