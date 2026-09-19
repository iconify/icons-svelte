<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8nh6fim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pa8nh6fim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:keyframe-plus-in-solid" {...props}></Icon>
