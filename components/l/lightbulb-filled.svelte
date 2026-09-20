<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipv-8xbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipv-8xbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lightbulb-filled" {...props}></Icon>
