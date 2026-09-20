<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0qpvg3uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0qpvg3uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-speaker-filled" {...props}></Icon>
