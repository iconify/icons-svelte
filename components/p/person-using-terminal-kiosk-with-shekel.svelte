<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg6-z-39m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rg6-z-39m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-shekel" {...props}></Icon>
