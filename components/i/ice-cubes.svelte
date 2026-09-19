<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvp1kxbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvp1kxbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ice-cubes" {...props}></Icon>
