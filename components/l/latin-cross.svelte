<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_jribczu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d_jribczu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:latin-cross" {...props}></Icon>
