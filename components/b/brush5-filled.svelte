<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0xwgf8fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0xwgf8fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:brush5-filled" {...props}></Icon>
