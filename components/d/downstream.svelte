<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2iwfpb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h2iwfpb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:downstream" {...props}></Icon>
