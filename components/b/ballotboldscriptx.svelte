<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb76z_6xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bb76z_6xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ballotboldscriptx" {...props}></Icon>
