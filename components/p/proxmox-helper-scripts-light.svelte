<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkcum6bdj.css';
import '../../css/e/e-q1i1bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkcum6bdj"/><path class="e-q1i1bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox-helper-scripts-light" {...props}></Icon>
