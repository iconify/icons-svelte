<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj8wxne4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj8wxne4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-r-duotone-round" {...props}></Icon>
