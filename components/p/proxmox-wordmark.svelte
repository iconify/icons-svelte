<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5pyydzvd.css';
import '../../css/w/w_gpdib1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q5pyydzvd"/><path class="w_gpdib1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:proxmox-wordmark" {...props}></Icon>
