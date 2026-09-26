<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fj27cp7nx.css';
import '../../css/n/nwp387s1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="fj27cp7nx"/><path class="nwp387s1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-circle-outline" {...props}></Icon>
