<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d39ld9bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d39ld9bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:airplane" {...props}></Icon>
