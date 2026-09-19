<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1fjhccnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1fjhccnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-heart-half" {...props}></Icon>
