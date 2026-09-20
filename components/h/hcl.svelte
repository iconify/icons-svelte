<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd1rn1bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd1rn1bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hcl" {...props}></Icon>
