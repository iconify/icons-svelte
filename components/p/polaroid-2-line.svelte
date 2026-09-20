<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgp-hdafg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgp-hdafg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:polaroid-2-line" {...props}></Icon>
