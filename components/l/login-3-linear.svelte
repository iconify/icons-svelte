<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/npjnncbsm.css';
import '../../css/v/v0-ucqeuw.css';
import '../../css/g/g_eh3ebdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="npjnncbsm"/><path class="v0-ucqeuw"/><path class="g_eh3ebdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-3-linear" {...props}></Icon>
