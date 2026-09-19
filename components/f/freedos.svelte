<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw36togob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vw36togob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:freedos" {...props}></Icon>
