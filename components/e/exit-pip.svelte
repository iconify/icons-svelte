<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w71pcf2_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w71pcf2_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:exit-pip" {...props}></Icon>
