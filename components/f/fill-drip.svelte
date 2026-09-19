<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ok3ubhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="y7ok3ubhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fill-drip" {...props}></Icon>
