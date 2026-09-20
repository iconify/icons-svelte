<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brc8u4q-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="brc8u4q-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:caret-left" {...props}></Icon>
