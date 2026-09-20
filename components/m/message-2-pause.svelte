<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twqi1ol-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twqi1ol-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-pause" {...props}></Icon>
