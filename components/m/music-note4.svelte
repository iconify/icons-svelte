<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9ilaybrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9ilaybrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note4" {...props}></Icon>
