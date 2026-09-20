<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4d2-cb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v4d2-cb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:petrine-cross" {...props}></Icon>
