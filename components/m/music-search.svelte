<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjn3wobdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjn3wobdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-search" {...props}></Icon>
