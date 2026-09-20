<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bof77n6om.css';
import '../../css/m/mn9zp8bxl.css';
import '../../css/j/jr5b5nohz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bof77n6om"/><path class="mn9zp8bxl"/><path class="jr5b5nohz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:haskell" {...props}></Icon>
