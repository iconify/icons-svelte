<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttp7_shbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ttp7_shbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:onion-roof-shape" {...props}></Icon>
