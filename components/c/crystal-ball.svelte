<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm5_z2x2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm5_z2x2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crystal-ball" {...props}></Icon>
