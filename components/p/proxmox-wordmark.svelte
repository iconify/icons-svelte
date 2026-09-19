<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1bxtwk9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v1bxtwk9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:proxmox-wordmark" {...props}></Icon>
