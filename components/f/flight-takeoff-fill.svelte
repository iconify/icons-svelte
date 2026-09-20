<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs1r29bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs1r29bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flight-takeoff-fill" {...props}></Icon>
