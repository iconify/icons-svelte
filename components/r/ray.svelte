<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp_v__9ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_v__9ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ray" {...props}></Icon>
