<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rccfyt4vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rccfyt4vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:light-bulb-24" {...props}></Icon>
