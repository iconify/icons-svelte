<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo2yj5prd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qo2yj5prd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:camera" {...props}></Icon>
