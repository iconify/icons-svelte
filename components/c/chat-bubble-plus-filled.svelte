<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m02bcib0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m02bcib0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-plus-filled" {...props}></Icon>
