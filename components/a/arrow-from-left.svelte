<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iglgn19tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iglgn19tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:arrow-from-left" {...props}></Icon>
