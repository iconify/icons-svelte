<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my2j24b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="my2j24b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-5" {...props}></Icon>
