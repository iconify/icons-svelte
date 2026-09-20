<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rho5ahrvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rho5ahrvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:poker-clubs-fill" {...props}></Icon>
