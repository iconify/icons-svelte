<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0-5-9fnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x0-5-9fnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-in-stroke-16" {...props}></Icon>
