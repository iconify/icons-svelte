<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmuxh0buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmuxh0buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-layout-footer" {...props}></Icon>
