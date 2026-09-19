<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppl-i9bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ppl-i9bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:accessible-icon" {...props}></Icon>
