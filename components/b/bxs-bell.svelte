<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjqg-lw3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjqg-lw3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bell" {...props}></Icon>
