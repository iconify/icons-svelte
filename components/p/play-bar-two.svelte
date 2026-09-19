<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd1z4ji4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd1z4ji4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-two" {...props}></Icon>
