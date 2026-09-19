<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljaub6bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljaub6bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:radio-off" {...props}></Icon>
