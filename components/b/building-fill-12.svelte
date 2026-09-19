<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awuo_7k1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="awuo_7k1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-fill-12" {...props}></Icon>
