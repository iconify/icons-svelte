<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw3bu8blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jw3bu8blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:forward-10-bold" {...props}></Icon>
