<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4p89lbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w4p89lbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:expressdotjs-light" {...props}></Icon>
