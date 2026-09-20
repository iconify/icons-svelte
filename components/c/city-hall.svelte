<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffx8j-san.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ffx8j-san"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:city-hall" {...props}></Icon>
