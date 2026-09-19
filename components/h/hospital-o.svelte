<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aidoxu2xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="aidoxu2xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hospital-o" {...props}></Icon>
