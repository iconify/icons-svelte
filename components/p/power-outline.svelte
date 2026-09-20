<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6i9_yb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x6i9_yb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:power-outline" {...props}></Icon>
