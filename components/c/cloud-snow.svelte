<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxgef79ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jxgef79ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-snow" {...props}></Icon>
