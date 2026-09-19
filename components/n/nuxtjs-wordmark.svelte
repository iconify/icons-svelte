<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h463hc-oe.css';
import '../../css/q/qakety7sc.css';
import '../../css/x/xr5cjkbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h463hc-oe"/><path class="qakety7sc"/><path class="xr5cjkbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nuxtjs-wordmark" {...props}></Icon>
