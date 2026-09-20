<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fho66jkja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="fho66jkja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:fire" {...props}></Icon>
