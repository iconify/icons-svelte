<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmxmzcctl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmxmzcctl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:microscope-fill" {...props}></Icon>
