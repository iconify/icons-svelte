<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d503q0bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d503q0bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-bold" {...props}></Icon>
