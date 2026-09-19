<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8xhx3bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="a8xhx3bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:home" {...props}></Icon>
