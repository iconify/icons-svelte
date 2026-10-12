<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug3_nnb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ug3_nnb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dots-horizontal-20" {...props}></Icon>
