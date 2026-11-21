<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg5vvtsnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":215.696,"height":215.696,"left":20.152,"top":20.152};
const content = `<path class="vg5vvtsnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:general-translation-light" {...props}></Icon>
