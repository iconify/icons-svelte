<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-sv5cbsg.css';
import '../../css/e/ejoji3b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-sv5cbsg"/><path class="ejoji3b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:houses-filled" {...props}></Icon>
