<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6tbcgbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6tbcgbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fortinet-light" {...props}></Icon>
