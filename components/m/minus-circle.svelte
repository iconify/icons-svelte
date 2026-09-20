<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pieq7wvlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pieq7wvlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:minus-circle" {...props}></Icon>
