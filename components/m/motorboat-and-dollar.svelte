<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foxqnjf9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="foxqnjf9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-dollar" {...props}></Icon>
