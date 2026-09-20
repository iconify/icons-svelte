<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl479qbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl479qbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:egg-off" {...props}></Icon>
