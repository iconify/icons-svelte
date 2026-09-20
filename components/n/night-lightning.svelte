<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfzld3bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="yfzld3bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-lightning" {...props}></Icon>
