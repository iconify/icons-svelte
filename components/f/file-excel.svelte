<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgwwk6bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lgwwk6bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-excel" {...props}></Icon>
