<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq3_6fbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="oq3_6fbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:broom" {...props}></Icon>
