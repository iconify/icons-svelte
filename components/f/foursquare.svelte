<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzck6r5dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":512};
const content = `<path class="bzck6r5dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:foursquare" {...props}></Icon>
