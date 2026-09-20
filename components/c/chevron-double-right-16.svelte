<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7bd_m0le.css';
import '../../css/d/dg4ly5vpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7bd_m0le"/><path clip-rule="evenodd" class="dg4ly5vpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-double-right-16" {...props}></Icon>
