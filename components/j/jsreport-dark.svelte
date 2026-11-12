<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnxapn8mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hnxapn8mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jsreport-dark" {...props}></Icon>
