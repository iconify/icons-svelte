<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hse_63wgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hse_63wgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:airport" {...props}></Icon>
