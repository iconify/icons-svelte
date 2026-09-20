<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0yr73bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n0yr73bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pin-outline" {...props}></Icon>
