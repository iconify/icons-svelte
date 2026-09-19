<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqrbplbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aqrbplbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:alien-monster" {...props}></Icon>
