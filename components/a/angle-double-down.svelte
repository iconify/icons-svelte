<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo4avb77y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1280};
const content = `<g transform="translate(0 1280) scale(1 -1)"><path class="bo4avb77y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angle-double-down" {...props}></Icon>
