<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnb388bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hnb388bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:luggage" {...props}></Icon>
