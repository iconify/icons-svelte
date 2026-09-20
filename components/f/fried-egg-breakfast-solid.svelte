<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inp-gjbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="inp-gjbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fried-egg-breakfast-solid" {...props}></Icon>
