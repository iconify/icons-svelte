<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubnxg2ces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ubnxg2ces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angles-down" {...props}></Icon>
