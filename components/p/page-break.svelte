<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7-lexb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="r7-lexb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:page-break" {...props}></Icon>
