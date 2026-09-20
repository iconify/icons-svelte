<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta-gi97mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ta-gi97mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-inside" {...props}></Icon>
