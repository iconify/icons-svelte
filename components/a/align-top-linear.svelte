<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m7r8ebbdl.css';
import '../../css/m/mnjv0ybzu.css';
import '../../css/a/af53pzb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m7r8ebbdl"/><path class="mnjv0ybzu"/><path class="af53pzb1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-top-linear" {...props}></Icon>
