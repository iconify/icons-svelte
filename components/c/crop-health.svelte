<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n85e_ljup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n85e_ljup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:crop-health" {...props}></Icon>
