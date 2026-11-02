<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwo770bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwo770bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-plus-inside-line" {...props}></Icon>
