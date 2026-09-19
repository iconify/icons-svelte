<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdpeolgsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qdpeolgsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cart2" {...props}></Icon>
