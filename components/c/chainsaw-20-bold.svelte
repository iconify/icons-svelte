<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyhy5lb0z.css';
import '../../css/c/cxf3gybkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gyhy5lb0z"/><path class="cxf3gybkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chainsaw-20-bold" {...props}></Icon>
