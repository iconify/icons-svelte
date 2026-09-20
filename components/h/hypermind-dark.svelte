<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdf7nmbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xdf7nmbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hypermind-dark" {...props}></Icon>
