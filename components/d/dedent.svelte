<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t630uobct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="t630uobct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:dedent" {...props}></Icon>
