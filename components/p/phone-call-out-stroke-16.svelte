<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjhjembnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mjhjembnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-out-stroke-16" {...props}></Icon>
