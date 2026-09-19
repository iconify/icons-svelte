<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg9-v1ver.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gg9-v1ver"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-ll" {...props}></Icon>
