<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb0b3q3bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sb0b3q3bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-military-to-person" {...props}></Icon>
