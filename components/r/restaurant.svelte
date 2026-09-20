<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4qobc7z.css';
import '../../css/z/z3jcjnr1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="td4qobc7z"/><path class="z3jcjnr1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:restaurant" {...props}></Icon>
