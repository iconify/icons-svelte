<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppzlhhbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ppzlhhbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-down-vertical-stipple-left" {...props}></Icon>
