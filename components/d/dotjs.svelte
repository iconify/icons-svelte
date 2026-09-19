<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umcw9nm8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="umcw9nm8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dotjs" {...props}></Icon>
