<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuevs1bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary uuevs1bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:low-bandwidth-duotone" {...props}></Icon>
