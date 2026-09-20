<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq9-xobpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":62.846,"height":60.485,"left":98.638,"top":11.193};
const content = `<path class="dq9-xobpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:knowbe4" {...props}></Icon>
