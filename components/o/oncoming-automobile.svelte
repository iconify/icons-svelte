<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey6g4lbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ey6g4lbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:oncoming-automobile" {...props}></Icon>
