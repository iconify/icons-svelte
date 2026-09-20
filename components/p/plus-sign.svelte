<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_hak7-9q.css';
import '../../css/n/n8g0hetvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="y_hak7-9q"/><path class="n8g0hetvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:plus-sign" {...props}></Icon>
