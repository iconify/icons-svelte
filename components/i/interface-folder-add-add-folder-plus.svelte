<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4b2zt-qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r4b2zt-qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-folder-add-add-folder-plus" {...props}></Icon>
