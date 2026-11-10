<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok65zv8cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ok65zv8cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-check-20-solid" {...props}></Icon>
