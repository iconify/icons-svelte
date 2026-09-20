<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j59i0pbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j59i0pbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folding-fan-fill" {...props}></Icon>
