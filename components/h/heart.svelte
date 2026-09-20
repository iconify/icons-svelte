<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crhleorvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="crhleorvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:heart" {...props}></Icon>
