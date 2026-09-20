<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy0t6ac2f.css';
import '../../css/m/m3biyk1pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0t6ac2f"/><path class="m3biyk1pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:racket-ball-duotone" {...props}></Icon>
