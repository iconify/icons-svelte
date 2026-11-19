<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geid27cpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="geid27cpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:apacheflink" {...props}></Icon>
