<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maztft4oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maztft4oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pulse-24" {...props}></Icon>
