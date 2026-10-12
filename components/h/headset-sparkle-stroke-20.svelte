<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or1v_l28y.css';
import '../../css/m/mhnbjolts.css';
import '../../css/p/pfqjkwvxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="or1v_l28y"/><path class="mhnbjolts"/><path class="pfqjkwvxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-sparkle-stroke-20" {...props}></Icon>
