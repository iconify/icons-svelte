<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a00fyudwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a00fyudwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:dribbble-outline" {...props}></Icon>
