<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex8t8sbzj.css';
import '../../css/n/nyjz5ihhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ex8t8sbzj"/><path class="nyjz5ihhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-off-20" {...props}></Icon>
