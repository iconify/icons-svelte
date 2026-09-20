<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtx1i6bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qtx1i6bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hand-with-eye" {...props}></Icon>
