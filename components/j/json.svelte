<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no7qesbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="no7qesbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:json" {...props}></Icon>
