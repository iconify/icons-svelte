<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh_p4mbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oh_p4mbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-v" {...props}></Icon>
