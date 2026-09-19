<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl89ysb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wl89ysb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-bowing" {...props}></Icon>
