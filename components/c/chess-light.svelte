<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m25d_fb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m25d_fb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:chess-light" {...props}></Icon>
