<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8924ub-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8924ub-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-tack" {...props}></Icon>
