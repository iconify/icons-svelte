<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/una5hpbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="una5hpbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:pen-tool" {...props}></Icon>
