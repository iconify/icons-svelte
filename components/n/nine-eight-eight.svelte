<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re-flo1hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="re-flo1hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nine-eight-eight" {...props}></Icon>
