<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnc9p5h0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnc9p5h0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-a-z" {...props}></Icon>
