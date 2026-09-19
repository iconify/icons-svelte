<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fepkv5b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fepkv5b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:design" {...props}></Icon>
