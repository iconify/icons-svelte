<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h10gz5b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h10gz5b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:proxmox" {...props}></Icon>
