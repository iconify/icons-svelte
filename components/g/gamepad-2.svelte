<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap4pzbctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap4pzbctu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gamepad-2" {...props}></Icon>
