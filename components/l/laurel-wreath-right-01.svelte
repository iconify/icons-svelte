<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trfqa1tba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trfqa1tba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:laurel-wreath-right-01" {...props}></Icon>
