<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpjo1n7rm.css';
import '../../css/a/a1gawlb3a.css';
import '../../css/g/gyy97vb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="cpjo1n7rm"/><path class="a1gawlb3a"/><path class="gyy97vb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:map" {...props}></Icon>
