<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2lsgoblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v2lsgoblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-pound" {...props}></Icon>
