<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr1829flq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kr1829flq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-pawprint" {...props}></Icon>
