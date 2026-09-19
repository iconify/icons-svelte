<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckkltl1os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckkltl1os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:music-outline" {...props}></Icon>
