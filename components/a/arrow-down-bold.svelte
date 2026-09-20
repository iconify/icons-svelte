<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5k2-3dhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="t5k2-3dhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-bold" {...props}></Icon>
