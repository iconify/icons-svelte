<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa0resxcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qa0resxcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:laugh-squint" {...props}></Icon>
