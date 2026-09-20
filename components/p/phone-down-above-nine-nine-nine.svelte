<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_1tuyjpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j_1tuyjpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-nine-nine-nine" {...props}></Icon>
