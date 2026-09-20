<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy4wn9bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy4wn9bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:meteor" {...props}></Icon>
