<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckcjutb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckcjutb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pipette-linear" {...props}></Icon>
