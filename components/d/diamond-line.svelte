<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plx5kkbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plx5kkbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-line" {...props}></Icon>
