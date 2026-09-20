<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf06xvx1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf06xvx1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:heart-alt" {...props}></Icon>
