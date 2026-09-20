<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz_4aobwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz_4aobwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:honey" {...props}></Icon>
