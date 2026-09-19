<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2w0dfbzz.css';
import '../../css/x/xjlu6cc0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v2w0dfbzz"/><path class="xjlu6cc0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flag-fill-12" {...props}></Icon>
