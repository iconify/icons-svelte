<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re7f0xsad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re7f0xsad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bridge" {...props}></Icon>
