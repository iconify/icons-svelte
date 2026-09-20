<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxvf2ubem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vxvf2ubem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:collapse-right" {...props}></Icon>
