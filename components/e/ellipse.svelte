<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do-_nxtdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="do-_nxtdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ellipse" {...props}></Icon>
