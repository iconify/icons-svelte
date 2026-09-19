<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ux81thv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":370,"height":512};
const content = `<path class="t8ux81thv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pickle" {...props}></Icon>
