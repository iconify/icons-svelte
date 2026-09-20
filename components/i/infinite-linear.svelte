<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n708t0bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n708t0bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:infinite-linear" {...props}></Icon>
