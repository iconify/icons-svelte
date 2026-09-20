<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbngs4vpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gbngs4vpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pointer-left" {...props}></Icon>
