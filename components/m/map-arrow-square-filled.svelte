<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xibaxbc-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xibaxbc-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-arrow-square-filled" {...props}></Icon>
