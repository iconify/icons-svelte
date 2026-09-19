<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik01-rb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ik01-rb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:clamp" {...props}></Icon>
