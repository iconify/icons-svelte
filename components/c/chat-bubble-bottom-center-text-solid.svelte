<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz_vtj53w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz_vtj53w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-bottom-center-text-solid" {...props}></Icon>
