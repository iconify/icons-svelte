<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuzsnn-5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wuzsnn-5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-search-remove" {...props}></Icon>
