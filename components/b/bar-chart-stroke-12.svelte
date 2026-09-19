<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckpvr9csx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ckpvr9csx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-stroke-12" {...props}></Icon>
