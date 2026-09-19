<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of0et4brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of0et4brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-star-filled" {...props}></Icon>
