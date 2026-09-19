<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu0ox2bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu0ox2bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-4" {...props}></Icon>
