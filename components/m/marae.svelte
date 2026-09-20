<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1_80_b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d1_80_b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:marae" {...props}></Icon>
