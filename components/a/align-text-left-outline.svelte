<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r32gc8bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r32gc8bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-text-left-outline" {...props}></Icon>
