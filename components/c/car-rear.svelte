<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx40v78ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rx40v78ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:car-rear" {...props}></Icon>
