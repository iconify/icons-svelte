<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm1evfbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xm1evfbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-horizontal-outline" {...props}></Icon>
