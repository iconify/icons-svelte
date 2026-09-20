<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot1z51b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot1z51b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aboutdotme" {...props}></Icon>
