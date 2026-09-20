<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no9dh2d2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="no9dh2d2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:degrees" {...props}></Icon>
