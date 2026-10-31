<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w41rlbb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w41rlbb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:close-small-fill-round" {...props}></Icon>
