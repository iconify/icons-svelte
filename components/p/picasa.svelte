<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p19pt6bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p19pt6bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:picasa" {...props}></Icon>
