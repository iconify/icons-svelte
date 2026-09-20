<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcqr42bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcqr42bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:format-circle-filled" {...props}></Icon>
