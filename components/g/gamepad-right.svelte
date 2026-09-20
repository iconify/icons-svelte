<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-cfe4r_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="u-cfe4r_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-right" {...props}></Icon>
