<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz58j3bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fz58j3bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:incident-reporter" {...props}></Icon>
