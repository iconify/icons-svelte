<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzi4bo-8z.css';
import '../../css/a/a58tyvbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fzi4bo-8z"/><path class="a58tyvbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:image-stroke-20" {...props}></Icon>
