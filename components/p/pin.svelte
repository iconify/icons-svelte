<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfqs5rbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":432};
const content = `<path class="jfqs5rbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pin" {...props}></Icon>
