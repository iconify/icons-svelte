<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnhqg0bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnhqg0bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:easy-in-out-line" {...props}></Icon>
