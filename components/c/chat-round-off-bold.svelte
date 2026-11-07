<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghj3bdbyn.css';
import '../../css/s/sibe-iawq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghj3bdbyn"/><path class="sibe-iawq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-off-bold" {...props}></Icon>
