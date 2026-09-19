<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4r_iy55d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4r_iy55d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-narrow-wide" {...props}></Icon>
