<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shf32-ouq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shf32-ouq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cone" {...props}></Icon>
