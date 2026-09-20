<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6z_85bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6z_85bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fire-extinguisher" {...props}></Icon>
