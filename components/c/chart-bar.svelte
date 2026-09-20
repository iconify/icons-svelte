<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzt9c_6gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lzt9c_6gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chart-bar" {...props}></Icon>
