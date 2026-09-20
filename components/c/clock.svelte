<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mabwzbbvc.css';
import '../../css/a/a1sqeabop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mabwzbbvc"/><path class="a1sqeabop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:clock" {...props}></Icon>
