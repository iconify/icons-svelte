<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzyv8xbll.css';
import '../../css/t/t8atr7bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tzyv8xbll"/><path class="t8atr7bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:hearing-aid" {...props}></Icon>
