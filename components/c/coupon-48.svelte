<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlkz-3bot.css';
import '../../css/x/x5r2fk28b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nlkz-3bot"/><path class="x5r2fk28b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupon-48" {...props}></Icon>
