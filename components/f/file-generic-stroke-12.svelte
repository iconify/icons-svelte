<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyel1qbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eyel1qbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-generic-stroke-12" {...props}></Icon>
