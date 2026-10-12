<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqaun74ep.css';
import '../../css/l/lqmbin3sl.css';
import '../../css/m/mp47fxbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqaun74ep"/><path clip-rule="evenodd" class="lqmbin3sl"/><path class="mp47fxbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-pen-filled" {...props}></Icon>
