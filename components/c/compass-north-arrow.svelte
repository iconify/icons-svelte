<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwbdq-bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bwbdq-bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:compass-north-arrow" {...props}></Icon>
