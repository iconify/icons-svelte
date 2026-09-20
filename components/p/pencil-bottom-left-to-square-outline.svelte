<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6flzy-3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j6flzy-3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pencil-bottom-left-to-square-outline" {...props}></Icon>
