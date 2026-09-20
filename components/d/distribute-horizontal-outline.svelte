<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwakjcbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vwakjcbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:distribute-horizontal-outline" {...props}></Icon>
