<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/padqvg4vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="padqvg4vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-bridge-2" {...props}></Icon>
