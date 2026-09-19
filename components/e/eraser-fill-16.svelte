<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlzy1_b2o.css';
import '../../css/h/hv0axw6am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tlzy1_b2o"/><path class="hv0axw6am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eraser-fill-16" {...props}></Icon>
