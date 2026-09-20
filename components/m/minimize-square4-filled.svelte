<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrgibklam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrgibklam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minimize-square4-filled" {...props}></Icon>
