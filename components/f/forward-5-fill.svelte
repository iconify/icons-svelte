<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmuejzben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmuejzben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-5-fill" {...props}></Icon>
