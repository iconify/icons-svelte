<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2m-mqbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s2m-mqbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-stroke-12" {...props}></Icon>
