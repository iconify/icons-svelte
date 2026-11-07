<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/osuf_jq5d.css';
import '../../css/e/e85a4hbua.css';
import '../../css/q/q91-j3b0a.css';
import '../../css/q/q1cgl7rzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="osuf_jq5d"/><path class="e85a4hbua"/><path class="q91-j3b0a"/><path class="q1cgl7rzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-broken" {...props}></Icon>
