<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp2hfzgbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="tp2hfzgbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:chrome" {...props}></Icon>
