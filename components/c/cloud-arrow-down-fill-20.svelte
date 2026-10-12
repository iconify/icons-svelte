<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgm-muboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zgm-muboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cloud-arrow-down-fill-20" {...props}></Icon>
