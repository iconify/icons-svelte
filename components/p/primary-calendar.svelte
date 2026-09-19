<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1enz4oyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u1enz4oyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:primary-calendar" {...props}></Icon>
