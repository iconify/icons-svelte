<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gsp36vw2y.css';
import '../../css/i/i326cougr.css';
import '../../css/q/qw59k8t0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gsp36vw2y"/><path class="i326cougr"/><path class="qw59k8t0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-send-broken" {...props}></Icon>
