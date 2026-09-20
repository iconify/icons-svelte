<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ne7b7zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f_ne7b7zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-euro" {...props}></Icon>
