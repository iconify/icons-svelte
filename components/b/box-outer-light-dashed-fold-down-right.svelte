<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp70-nopp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yp70-nopp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-fold-down-right" {...props}></Icon>
