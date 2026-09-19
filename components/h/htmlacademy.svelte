<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns030dt4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ns030dt4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:htmlacademy" {...props}></Icon>
