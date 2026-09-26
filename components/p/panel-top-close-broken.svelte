<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bqpjtgv7n.css';
import '../../css/w/wip28lbxr.css';
import '../../css/q/quujejbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bqpjtgv7n"/><path class="wip28lbxr"/><path class="quujejbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-close-broken" {...props}></Icon>
