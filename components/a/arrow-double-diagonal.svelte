<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7lop2boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z7lop2boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-double-diagonal" {...props}></Icon>
