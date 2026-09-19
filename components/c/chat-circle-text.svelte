<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3_c0b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_3_c0b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-text" {...props}></Icon>
