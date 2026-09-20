<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meoj66rlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="meoj66rlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:call-1" {...props}></Icon>
