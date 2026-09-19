<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2cxap5ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="w2cxap5ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:kiss" {...props}></Icon>
