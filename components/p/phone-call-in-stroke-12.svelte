<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_u2c4bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="w_u2c4bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-in-stroke-12" {...props}></Icon>
