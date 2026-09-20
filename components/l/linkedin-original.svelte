<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxv7-tb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rxv7-tb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:linkedin-original" {...props}></Icon>
