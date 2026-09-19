<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv9h8h9hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv9h8h9hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:fingerprint" {...props}></Icon>
