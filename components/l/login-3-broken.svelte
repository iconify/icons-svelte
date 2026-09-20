<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/so2izg5eh.css';
import '../../css/v/v0-ucqeuw.css';
import '../../css/j/jsl6qobau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="so2izg5eh"/><path class="v0-ucqeuw"/><path class="jsl6qobau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-3-broken" {...props}></Icon>
