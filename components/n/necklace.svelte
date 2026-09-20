<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uba5k61oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="uba5k61oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:necklace" {...props}></Icon>
