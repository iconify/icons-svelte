<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4fb2tf6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t4fb2tf6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:markup-stroke-12" {...props}></Icon>
