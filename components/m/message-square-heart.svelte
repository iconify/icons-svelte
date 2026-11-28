<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of36-uh_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of36-uh_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-heart" {...props}></Icon>
