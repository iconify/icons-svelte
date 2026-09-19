<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c42-7gvoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c42-7gvoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:globe" {...props}></Icon>
