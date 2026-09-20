<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1t0v7bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h1t0v7bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-down-right-circle" {...props}></Icon>
