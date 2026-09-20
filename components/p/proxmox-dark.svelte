<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_yo0bqco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_yo0bqco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox-dark" {...props}></Icon>
