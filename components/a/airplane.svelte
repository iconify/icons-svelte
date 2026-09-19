<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xne1tcxxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xne1tcxxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:airplane" {...props}></Icon>
