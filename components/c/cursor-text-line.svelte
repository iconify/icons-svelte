<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqcbpabrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqcbpabrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-text-line" {...props}></Icon>
