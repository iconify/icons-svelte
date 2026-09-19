<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hota12b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":384};
const content = `<path class="hota12b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:fast-forward" {...props}></Icon>
