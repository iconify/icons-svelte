<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlrierb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlrierb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eject" {...props}></Icon>
