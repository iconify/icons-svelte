<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx7v_41ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx7v_41ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:para-swap" {...props}></Icon>
