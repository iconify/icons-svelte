<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crtk_e-gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crtk_e-gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kick-scooter-linear" {...props}></Icon>
