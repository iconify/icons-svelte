<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa5x1dblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sa5x1dblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-vis-4" {...props}></Icon>
