<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvk8v6b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gvk8v6b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-excel-fill" {...props}></Icon>
