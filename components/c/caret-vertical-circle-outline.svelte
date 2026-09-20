<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdrxi_5qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mdrxi_5qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:caret-vertical-circle-outline" {...props}></Icon>
