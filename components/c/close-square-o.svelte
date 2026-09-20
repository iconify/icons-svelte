<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sla9g7bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sla9g7bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:close-square-o" {...props}></Icon>
