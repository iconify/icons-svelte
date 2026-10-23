<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usds7cush.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usds7cush"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gamepad" {...props}></Icon>
