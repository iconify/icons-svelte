<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsjjrqb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsjjrqb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cigarette-off" {...props}></Icon>
