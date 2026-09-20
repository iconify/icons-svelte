<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcmnq--uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcmnq--uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-n-filled" {...props}></Icon>
