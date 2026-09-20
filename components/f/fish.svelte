<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7sh_2rdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l7sh_2rdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fish" {...props}></Icon>
