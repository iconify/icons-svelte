<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twfrwunxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twfrwunxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:groly-light" {...props}></Icon>
