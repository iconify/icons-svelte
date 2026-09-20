<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyz00n_yo.css';
import '../../css/o/ojcn0pbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zyz00n_yo"/><path class="ojcn0pbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-perfume-1" {...props}></Icon>
