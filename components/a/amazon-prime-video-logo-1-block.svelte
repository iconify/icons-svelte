<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmqp0_b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmqp0_b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amazon-prime-video-logo-1-block" {...props}></Icon>
