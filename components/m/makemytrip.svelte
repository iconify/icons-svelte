<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7dbbrb5t.css';
import '../../css/h/hp-202bvr.css';
import '../../css/r/rg72-z8_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1558,"height":496};
const content = `<path class="c7dbbrb5t"/><path class="hp-202bvr"/><path class="rg72-z8_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:makemytrip" {...props}></Icon>
