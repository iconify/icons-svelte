<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyjp6ob9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lyjp6ob9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:blocked-site-solid-12" {...props}></Icon>
