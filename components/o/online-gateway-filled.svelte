<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs9fgmbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cs9fgmbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:online-gateway-filled" {...props}></Icon>
