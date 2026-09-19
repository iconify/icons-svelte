<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebxhznbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ebxhznbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:refresh-sync-problem" {...props}></Icon>
