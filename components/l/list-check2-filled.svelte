<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl7_c774e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dl7_c774e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-check2-filled" {...props}></Icon>
