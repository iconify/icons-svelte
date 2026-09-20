<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39thnbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e39thnbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:club-chair" {...props}></Icon>
