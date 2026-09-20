<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aseyl3-sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aseyl3-sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-down-arrow-down-keyboard" {...props}></Icon>
