<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqp0mzztf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqp0mzztf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:journiv-light" {...props}></Icon>
