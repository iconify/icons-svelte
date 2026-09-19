<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2jrgebvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b s2jrgebvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:gemini" {...props}></Icon>
