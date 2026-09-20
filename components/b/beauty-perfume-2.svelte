<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c73ylccim.css';
import '../../css/p/pozja0bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c73ylccim"/><path class="pozja0bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-perfume-2" {...props}></Icon>
