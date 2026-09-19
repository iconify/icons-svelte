<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgdj3873d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rgdj3873d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ranking-star" {...props}></Icon>
