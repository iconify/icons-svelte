<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/magta5rkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="magta5rkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:departure" {...props}></Icon>
