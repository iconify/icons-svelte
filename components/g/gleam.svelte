<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqnxzwb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqnxzwb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gleam" {...props}></Icon>
