<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usmd_2bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="usmd_2bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openmediavault-dark" {...props}></Icon>
