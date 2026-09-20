<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9ou1wbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ou1wbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-n" {...props}></Icon>
