<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijhq98bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijhq98bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:charging-bolt" {...props}></Icon>
