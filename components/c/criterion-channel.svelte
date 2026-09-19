<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbr_9nbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbr_9nbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:criterion-channel" {...props}></Icon>
