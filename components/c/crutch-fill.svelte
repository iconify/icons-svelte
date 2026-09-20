<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjctc-bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjctc-bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:crutch-fill" {...props}></Icon>
