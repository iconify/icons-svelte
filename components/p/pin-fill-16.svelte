<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1rbdbbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d1rbdbbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-fill-16" {...props}></Icon>
