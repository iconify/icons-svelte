<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrtzwyj8v.css';
import '../../css/i/iiwuq1b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lrtzwyj8v"/><path class="iiwuq1b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-add" {...props}></Icon>
