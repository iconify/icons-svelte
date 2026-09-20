<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0opr_u6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b0opr_u6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-baht" {...props}></Icon>
