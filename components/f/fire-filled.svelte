<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgtekh6ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pgtekh6ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:fire-filled" {...props}></Icon>
