<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x33k5bbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x33k5bbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cross-seed-dark" {...props}></Icon>
