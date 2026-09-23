<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tibe2sbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tibe2sbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cetusguard-light" {...props}></Icon>
