<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btxd_x04d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="btxd_x04d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lyre" {...props}></Icon>
