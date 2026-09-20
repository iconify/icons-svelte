<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5djgcb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5djgcb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gemini-google" {...props}></Icon>
