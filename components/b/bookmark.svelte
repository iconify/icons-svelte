<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbj_pyy4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mbj_pyy4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bookmark" {...props}></Icon>
