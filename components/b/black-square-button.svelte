<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsfengbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wsfengbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:black-square-button" {...props}></Icon>
