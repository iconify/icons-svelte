<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etm1unpln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="etm1unpln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-1" {...props}></Icon>
