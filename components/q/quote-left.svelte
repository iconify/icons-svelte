<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr0zt0kgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr0zt0kgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:quote-left" {...props}></Icon>
