<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr2i9yi8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1472};
const content = `<path class="tr2i9yi8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:gantt" {...props}></Icon>
