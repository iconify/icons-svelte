<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn4siwm2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":261.922,"height":345.941};
const content = `<path class="pn4siwm2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:penpot-light" {...props}></Icon>
