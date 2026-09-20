<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt9p4zb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lt9p4zb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-succeed-filled" {...props}></Icon>
