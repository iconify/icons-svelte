<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pab-3wh6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pab-3wh6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:moon-off" {...props}></Icon>
