<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xha8meb5n.css';
import '../../css/o/owtzvwbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xha8meb5n"/><path class="owtzvwbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:plane-private" {...props}></Icon>
