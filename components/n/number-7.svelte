<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep6igybrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ep6igybrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-7" {...props}></Icon>
