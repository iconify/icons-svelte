<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtn98vbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vtn98vbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:plus-rectangle-fill-on-rectangle-fill" {...props}></Icon>
