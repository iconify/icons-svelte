<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezxtsdbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezxtsdbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-h-filled" {...props}></Icon>
