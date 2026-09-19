<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/rdjp0q8rs.css';
import '../../css/k/k_zqo0b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="rdjp0q8rs"/><path class="k_zqo0b2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-4-outline" {...props}></Icon>
