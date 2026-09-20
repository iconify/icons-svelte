<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-3dycbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r-3dycbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:diploma-scroll" {...props}></Icon>
