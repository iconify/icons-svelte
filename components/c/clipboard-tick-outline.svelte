<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uax_rrxbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uax_rrxbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-tick-outline" {...props}></Icon>
