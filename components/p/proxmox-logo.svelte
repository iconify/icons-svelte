<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbay4z5qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbay4z5qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:proxmox-logo" {...props}></Icon>
