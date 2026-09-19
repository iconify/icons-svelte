<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vla2mvb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vla2mvb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:on-arrow" {...props}></Icon>
