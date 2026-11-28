<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz1upf8ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz1upf8ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hand-coin" {...props}></Icon>
