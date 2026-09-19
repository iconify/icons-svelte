<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5o7lacsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w5o7lacsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-4" {...props}></Icon>
