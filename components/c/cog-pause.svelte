<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pez1t_b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pez1t_b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-pause" {...props}></Icon>
