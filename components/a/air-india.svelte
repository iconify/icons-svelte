<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_jglacoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_jglacoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:air-india" {...props}></Icon>
