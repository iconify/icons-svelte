<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuko_16oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tuko_16oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-all" {...props}></Icon>
