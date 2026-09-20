<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di0umsr9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="di0umsr9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:question" {...props}></Icon>
