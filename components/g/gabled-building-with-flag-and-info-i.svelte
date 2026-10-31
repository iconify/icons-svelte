<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx3qwj2_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xx3qwj2_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-flag-and-info-i" {...props}></Icon>
