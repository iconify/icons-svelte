<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov13c6xvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ov13c6xvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:lollipop" {...props}></Icon>
