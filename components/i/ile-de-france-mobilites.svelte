<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wulzfdbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wulzfdbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ile-de-france-mobilites" {...props}></Icon>
