<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsdj_dbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xsdj_dbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-l" {...props}></Icon>
