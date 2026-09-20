<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg99jbc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wg99jbc7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:clockwise-90-filled" {...props}></Icon>
