<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy1ef0rgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="uy1ef0rgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:construction-hammer" {...props}></Icon>
