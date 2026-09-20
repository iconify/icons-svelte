<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/c/ce6gc0-_s.css';
import '../../css/i/ijsfpibqm.css';
import '../../css/m/m-nuw3bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ce6gc0-_s"/><path class="ijsfpibqm"/><path class="m-nuw3bni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:authy-logo" {...props}></Icon>
