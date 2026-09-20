<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibqkk_jsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ibqkk_jsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-baht" {...props}></Icon>
