<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkvs36v4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkvs36v4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gemma-google" {...props}></Icon>
