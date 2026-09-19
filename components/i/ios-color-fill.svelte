<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp35ndvma.css';
import '../../css/x/xyg2e4p_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp35ndvma"/><path class="xyg2e4p_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-color-fill" {...props}></Icon>
