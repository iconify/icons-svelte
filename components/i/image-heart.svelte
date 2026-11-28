<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnzvm5byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnzvm5byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-heart" {...props}></Icon>
