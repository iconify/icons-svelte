<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb8_pwp8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rb8_pwp8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:chart" {...props}></Icon>
