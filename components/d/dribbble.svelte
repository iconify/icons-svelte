<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et58hkbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="et58hkbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:dribbble" {...props}></Icon>
