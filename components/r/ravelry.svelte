<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9vlg2rrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9vlg2rrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:ravelry" {...props}></Icon>
