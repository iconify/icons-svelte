<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqb2d8bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nqb2d8bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-right-8" {...props}></Icon>
