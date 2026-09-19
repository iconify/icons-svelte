<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gypgt4b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="gypgt4b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:book" {...props}></Icon>
