<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw9gvkbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vw9gvkbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:play-circle-outline" {...props}></Icon>
