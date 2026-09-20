<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlvp0pbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="nlvp0pbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-right-stipple" {...props}></Icon>
