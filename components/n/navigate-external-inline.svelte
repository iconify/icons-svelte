<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4fp7zb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q4fp7zb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:navigate-external-inline" {...props}></Icon>
