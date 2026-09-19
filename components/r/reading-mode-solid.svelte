<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlb9wd9vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rlb9wd9vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reading-mode-solid" {...props}></Icon>
