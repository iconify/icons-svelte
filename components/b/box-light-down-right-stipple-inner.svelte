<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1ya0l6ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v1ya0l6ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-down-right-stipple-inner" {...props}></Icon>
