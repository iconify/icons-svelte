<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9_teob1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m9_teob1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:at-symbol" {...props}></Icon>
