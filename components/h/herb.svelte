<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9tcidckd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9tcidckd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:herb" {...props}></Icon>
