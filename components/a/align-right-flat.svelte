<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzlt_3t1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wzlt_3t1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:align-right-flat" {...props}></Icon>
