<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/ymwuqkrmm.css';
import '../../css/m/mdnzfy8ny.css';
import '../../css/e/e9_804b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ymwuqkrmm"/><path class="mdnzfy8ny"/><path class="e9_804b6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pen-off-sharp-two-tone" {...props}></Icon>
