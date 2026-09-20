<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi0s6-w3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gi0s6-w3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-left" {...props}></Icon>
