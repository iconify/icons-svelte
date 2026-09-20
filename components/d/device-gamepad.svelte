<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/optm_q_ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="optm_q_ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-gamepad" {...props}></Icon>
