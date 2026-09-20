<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuutoabwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuutoabwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chat-bubble-2" {...props}></Icon>
