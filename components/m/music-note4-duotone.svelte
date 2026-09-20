<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-ttllwtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ttllwtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note4-duotone" {...props}></Icon>
