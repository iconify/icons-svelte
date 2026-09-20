<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cokt-3b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cokt-3b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qq" {...props}></Icon>
