<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usonzhgnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="usonzhgnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rearrange-stroke-20" {...props}></Icon>
