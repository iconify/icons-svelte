<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb_4-lefx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb_4-lefx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:goblet-broken-line" {...props}></Icon>
