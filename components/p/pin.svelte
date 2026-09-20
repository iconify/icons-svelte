<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awajley2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="awajley2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:pin" {...props}></Icon>
