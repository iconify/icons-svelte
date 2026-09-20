<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpa7wsbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpa7wsbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:node-red" {...props}></Icon>
