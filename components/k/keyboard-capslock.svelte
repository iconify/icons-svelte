<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-tn2ibdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-tn2ibdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-capslock" {...props}></Icon>
