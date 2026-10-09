<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oix55f0zb.css';
import '../../css/z/zpidxlb0a.css';
import '../../css/i/ivx8nobtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oix55f0zb"/><path class="zpidxlb0a"/><path class="ivx8nobtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offset-20" {...props}></Icon>
