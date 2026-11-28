<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2boidcuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2boidcuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brain-solid" {...props}></Icon>
