<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va-uq9b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="va-uq9b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chat-sparkle-warning" {...props}></Icon>
