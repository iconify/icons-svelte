<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs39i-btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qs39i-btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:google-drive-logo" {...props}></Icon>
