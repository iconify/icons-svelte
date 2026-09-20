<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xrleuvbus.css';
import '../../css/v/v-ezbrn8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xrleuvbus"/><path class="v-ezbrn8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-pin-x" {...props}></Icon>
