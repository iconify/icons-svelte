<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeolk1tpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qeolk1tpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:management-stockout-filled" {...props}></Icon>
