<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjrotzbpr.css';
import '../../css/w/wgckvftty.css';
import '../../css/w/wh72mu7bx.css';
import '../../css/d/db6ijebmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="vjrotzbpr"/><rect class="wgckvftty"/><rect class="wh72mu7bx"/><rect class="db6ijebmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:columns-4-filled" {...props}></Icon>
