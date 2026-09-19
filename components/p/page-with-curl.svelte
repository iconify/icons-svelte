<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z23109bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z23109bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:page-with-curl" {...props}></Icon>
