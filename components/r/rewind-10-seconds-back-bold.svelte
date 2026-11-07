<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikfqmnb8s.css';
import '../../css/j/jo6q_wbuz.css';
import '../../css/m/m0j83-9at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikfqmnb8s"/><path class="jo6q_wbuz"/><path clip-rule="evenodd" class="m0j83-9at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-10-seconds-back-bold" {...props}></Icon>
