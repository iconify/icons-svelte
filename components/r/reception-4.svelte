<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry30_kgre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ry30_kgre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:reception-4" {...props}></Icon>
