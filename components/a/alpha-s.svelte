<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt_hpirfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gt_hpirfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-s" {...props}></Icon>
