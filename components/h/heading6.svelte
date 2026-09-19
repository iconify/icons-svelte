<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leqyehr3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leqyehr3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heading6" {...props}></Icon>
