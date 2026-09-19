<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbpl-x4go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbpl-x4go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pulse-strong" {...props}></Icon>
