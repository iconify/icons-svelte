<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxy1mo78q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xxy1mo78q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-g" {...props}></Icon>
