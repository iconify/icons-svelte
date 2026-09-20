<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a73tt2brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a73tt2brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:hand-pointer-event-line" {...props}></Icon>
