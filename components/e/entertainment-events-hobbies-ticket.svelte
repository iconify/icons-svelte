<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e95aribsc.css';
import '../../css/u/uaa9tzbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e95aribsc"/><path class="uaa9tzbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-ticket" {...props}></Icon>
