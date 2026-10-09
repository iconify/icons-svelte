<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8xiwibfs.css';
import '../../css/f/fad7f9tkf.css';
import '../../css/n/np3f-jntl.css';
import '../../css/d/dcgjitb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z8xiwibfs"/><path class="fad7f9tkf"/><path class="np3f-jntl"/><path class="dcgjitb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-capture-20-bold" {...props}></Icon>
