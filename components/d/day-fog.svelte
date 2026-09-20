<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxs2libfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="uxs2libfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-fog" {...props}></Icon>
