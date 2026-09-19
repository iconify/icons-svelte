<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf_a4xbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf_a4xbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beehiiv" {...props}></Icon>
