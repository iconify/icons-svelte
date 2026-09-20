<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftz8nnb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="ftz8nnb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-mobile" {...props}></Icon>
