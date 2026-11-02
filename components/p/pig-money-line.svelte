<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcs19fbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcs19fbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pig-money-line" {...props}></Icon>
