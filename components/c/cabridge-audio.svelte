<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vobjp9-9u.css';
import '../../css/v/vgc92oekq.css';
import '../../css/f/fvq226bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vobjp9-9u"/><path class="vgc92oekq"/><path class="fvq226bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cabridge-audio" {...props}></Icon>
