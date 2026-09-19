<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrgl_sbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrgl_sbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-list-filled" {...props}></Icon>
