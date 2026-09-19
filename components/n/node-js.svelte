<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5mk84iud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h5mk84iud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:node-js" {...props}></Icon>
