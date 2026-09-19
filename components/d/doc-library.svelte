<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1rjp8umr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w1rjp8umr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:doc-library" {...props}></Icon>
