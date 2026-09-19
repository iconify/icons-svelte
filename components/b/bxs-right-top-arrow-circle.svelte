<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehhu9f5ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehhu9f5ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-right-top-arrow-circle" {...props}></Icon>
