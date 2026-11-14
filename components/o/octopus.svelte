<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axae4tbjw.css';
import '../../css/c/cmgm03bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="axae4tbjw"/><path class="cmgm03bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:octopus" {...props}></Icon>
