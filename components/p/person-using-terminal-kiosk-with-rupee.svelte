<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmrzg-4tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jmrzg-4tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-rupee" {...props}></Icon>
