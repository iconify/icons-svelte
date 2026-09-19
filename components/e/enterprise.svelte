<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q23s4ccja.css';
import '../../css/m/mn4wyk1sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q23s4ccja"/><path class="mn4wyk1sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:enterprise" {...props}></Icon>
