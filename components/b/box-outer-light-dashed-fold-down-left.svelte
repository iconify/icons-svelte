<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4ds2m-5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r4ds2m-5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-fold-down-left" {...props}></Icon>
