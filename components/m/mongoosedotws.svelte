<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgh6pkben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgh6pkben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mongoosedotws" {...props}></Icon>
