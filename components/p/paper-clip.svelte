<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thruo1biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="thruo1biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:paper-clip" {...props}></Icon>
