<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvepz4bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvepz4bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-audio-doorbell" {...props}></Icon>
