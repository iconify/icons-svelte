<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qszp67b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qszp67b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pine-tree-box" {...props}></Icon>
