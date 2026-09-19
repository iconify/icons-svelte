<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7_z7-b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f7_z7-b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:embed-photo" {...props}></Icon>
