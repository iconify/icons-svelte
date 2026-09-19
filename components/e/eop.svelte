<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7g3dsb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32,"left":1};
const content = `<path class="x7g3dsb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:eop" {...props}></Icon>
