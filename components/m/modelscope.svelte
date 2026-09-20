<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0t214a9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0t214a9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:modelscope" {...props}></Icon>
