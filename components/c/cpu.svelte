<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g42dr9bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g42dr9bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:cpu" {...props}></Icon>
