<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az9ogk10m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az9ogk10m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-2-fill" {...props}></Icon>
