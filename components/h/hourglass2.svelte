<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxywjfe4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pxywjfe4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass2" {...props}></Icon>
