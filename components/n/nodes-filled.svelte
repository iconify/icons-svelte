<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uea_xyb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uea_xyb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:nodes-filled" {...props}></Icon>
