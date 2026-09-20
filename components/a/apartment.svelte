<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1-5195me.css';
import '../../css/w/wyynnt73k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h1-5195me"/><path class="wyynnt73k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:apartment" {...props}></Icon>
