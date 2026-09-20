<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3-tpwpnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3-tpwpnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:express" {...props}></Icon>
