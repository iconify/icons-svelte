<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr75xkbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pr75xkbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:link" {...props}></Icon>
