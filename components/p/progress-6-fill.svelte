<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doi0wrpzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doi0wrpzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-6-fill" {...props}></Icon>
