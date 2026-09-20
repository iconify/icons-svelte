<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqur53baa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="mqur53baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-showers" {...props}></Icon>
