<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hml-ltb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hml-ltb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:butter" {...props}></Icon>
