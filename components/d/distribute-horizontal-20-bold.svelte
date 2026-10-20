<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbkt2actg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gbkt2actg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:distribute-horizontal-20-bold" {...props}></Icon>
