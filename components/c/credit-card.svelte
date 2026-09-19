<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc75m8d8n.css';
import '../../css/t/tzev64bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="mc75m8d8n"/><path class="tzev64bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:credit-card" {...props}></Icon>
