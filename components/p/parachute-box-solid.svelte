<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk7hu_bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kk7hu_bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:parachute-box-solid" {...props}></Icon>
