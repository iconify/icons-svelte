<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb4ig9byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yb4ig9byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-molar-tooth" {...props}></Icon>
