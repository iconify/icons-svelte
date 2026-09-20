<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fod000b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="fod000b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:courthouse-10" {...props}></Icon>
