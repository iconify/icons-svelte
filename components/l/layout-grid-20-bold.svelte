<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrzzoccmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xrzzoccmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-grid-20-bold" {...props}></Icon>
