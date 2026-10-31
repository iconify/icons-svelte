<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sol21dz1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sol21dz1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-days-fill-round" {...props}></Icon>
