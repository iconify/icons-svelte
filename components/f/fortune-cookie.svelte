<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhy-nmuzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nhy-nmuzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:fortune-cookie" {...props}></Icon>
