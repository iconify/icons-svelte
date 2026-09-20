<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3jvhdbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r3jvhdbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:action-undo" {...props}></Icon>
