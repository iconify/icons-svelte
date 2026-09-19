<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3n_o_sbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="more-horizontal-outline"><path class="Vector w3n_o_sbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:more-horizontal-outline" {...props}></Icon>
