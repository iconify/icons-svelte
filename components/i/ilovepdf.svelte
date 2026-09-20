<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veu278kya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veu278kya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ilovepdf" {...props}></Icon>
