<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riux-3art.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="riux-3art"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-csv" {...props}></Icon>
