<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whge_h7ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="whge_h7ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:calendar-star-solid" {...props}></Icon>
