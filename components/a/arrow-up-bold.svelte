<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi9a3ibsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi9a3ibsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-bold" {...props}></Icon>
