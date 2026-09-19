<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-0m7-b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-0m7-b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mirc" {...props}></Icon>
