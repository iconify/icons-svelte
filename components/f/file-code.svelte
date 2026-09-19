<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-iqi5fsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="r-iqi5fsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-code" {...props}></Icon>
