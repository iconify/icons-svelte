<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-5_y5zdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m-5_y5zdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-left-20-solid" {...props}></Icon>
