<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/salrc2btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="salrc2btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pve-ups-light" {...props}></Icon>
