<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_kk48bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="r_kk48bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:playstore" {...props}></Icon>
