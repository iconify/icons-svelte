<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiznykb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uiznykb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ref-evapotranspiration" {...props}></Icon>
