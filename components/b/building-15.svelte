<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiln49pnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eiln49pnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:building-15" {...props}></Icon>
