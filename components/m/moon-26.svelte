<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4s7-rm9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="o4s7-rm9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-26" {...props}></Icon>
