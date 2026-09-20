<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw0a2pbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw0a2pbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dji" {...props}></Icon>
