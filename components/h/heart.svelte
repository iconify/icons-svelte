<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7qzbly7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f7qzbly7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:heart" {...props}></Icon>
