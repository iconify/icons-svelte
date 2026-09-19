<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig4hymbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ig4hymbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-6" {...props}></Icon>
