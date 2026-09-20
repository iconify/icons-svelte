<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twud3tbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twud3tbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-x" {...props}></Icon>
