<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwrqztgnf.css';
import '../../css/d/dg2c6-gpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hwrqztgnf"/><path clip-rule="evenodd" class="dg2c6-gpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-double-left-16" {...props}></Icon>
