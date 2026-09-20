<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvnl2-5op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wvnl2-5op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:briefcase-alt-outline" {...props}></Icon>
