<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5-8z9xxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q5-8z9xxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:clinking-glasses" {...props}></Icon>
