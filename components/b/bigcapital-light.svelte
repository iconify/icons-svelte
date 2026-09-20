<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww9cxtb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ww9cxtb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bigcapital-light" {...props}></Icon>
