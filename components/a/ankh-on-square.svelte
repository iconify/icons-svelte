<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y88wtbtkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y88wtbtkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ankh-on-square" {...props}></Icon>
