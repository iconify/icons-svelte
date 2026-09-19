<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsmm88mdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsmm88mdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:java-enum" {...props}></Icon>
