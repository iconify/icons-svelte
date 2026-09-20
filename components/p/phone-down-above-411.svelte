<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-g6p_te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mp-g6p_te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-411" {...props}></Icon>
