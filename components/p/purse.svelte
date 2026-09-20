<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw9r1w66o.css';
import '../../css/k/kvq9f4byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw9r1w66o"/><path class="kvq9f4byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:purse" {...props}></Icon>
