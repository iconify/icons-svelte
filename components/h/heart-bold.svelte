<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arf4c6btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arf4c6btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-bold" {...props}></Icon>
