<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpqaeac_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpqaeac_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-spot-lamp" {...props}></Icon>
