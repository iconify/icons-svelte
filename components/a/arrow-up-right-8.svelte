<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re7iyuqoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="re7iyuqoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrow-up-right-8" {...props}></Icon>
