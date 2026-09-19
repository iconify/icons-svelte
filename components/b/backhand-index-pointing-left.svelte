<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yft98tjya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yft98tjya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:backhand-index-pointing-left" {...props}></Icon>
