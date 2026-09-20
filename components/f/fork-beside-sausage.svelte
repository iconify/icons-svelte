<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td1ir3b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="td1ir3b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fork-beside-sausage" {...props}></Icon>
