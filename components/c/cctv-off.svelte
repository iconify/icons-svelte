<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trk91ybqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trk91ybqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cctv-off" {...props}></Icon>
