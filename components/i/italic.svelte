<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm0l__b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rm0l__b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:italic" {...props}></Icon>
