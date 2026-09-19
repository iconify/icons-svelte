<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nedktqbjv.css';
import '../../css/x/xllyvnhhr.css';
import '../../css/u/ug10i-prr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="nedktqbjv"/><path clip-rule="evenodd" class="xllyvnhhr"/><path class="ug10i-prr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:attention" {...props}></Icon>
