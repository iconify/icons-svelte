<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym-0ijbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ym-0ijbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:recycling-symbol" {...props}></Icon>
