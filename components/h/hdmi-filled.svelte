<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oirm5y_yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oirm5y_yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hdmi-filled" {...props}></Icon>
