<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmx29iyrb.css';
import '../../css/g/g-mtc6bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vmx29iyrb"/><path class="g-mtc6bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:items-tree-16" {...props}></Icon>
