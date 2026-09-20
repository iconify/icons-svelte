<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyyu2o1ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyyu2o1ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eternal-vows" {...props}></Icon>
