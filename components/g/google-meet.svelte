<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l71gnlbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l71gnlbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:google-meet" {...props}></Icon>
