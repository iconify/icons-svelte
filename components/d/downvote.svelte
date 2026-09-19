<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dax7uhcrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dax7uhcrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:downvote" {...props}></Icon>
