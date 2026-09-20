<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgm5oubbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jgm5oubbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-peso" {...props}></Icon>
