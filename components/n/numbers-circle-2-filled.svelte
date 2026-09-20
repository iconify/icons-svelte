<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uecyfgbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uecyfgbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-circle-2-filled" {...props}></Icon>
