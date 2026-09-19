<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksz-h4b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksz-h4b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hourglass-off" {...props}></Icon>
