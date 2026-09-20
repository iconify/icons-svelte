<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icb0mwb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icb0mwb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-filled" {...props}></Icon>
