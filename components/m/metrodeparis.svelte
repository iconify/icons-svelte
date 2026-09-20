<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv9eo3bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv9eo3bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:metrodeparis" {...props}></Icon>
