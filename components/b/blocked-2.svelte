<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5-lc9bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="l5-lc9bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:blocked-2" {...props}></Icon>
