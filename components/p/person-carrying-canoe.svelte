<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqximjmbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bqximjmbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-carrying-canoe" {...props}></Icon>
