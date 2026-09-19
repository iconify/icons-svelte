<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwczvpbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gwczvpbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bicycle" {...props}></Icon>
