<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc75m8d8n.css';
import '../../css/r/rkf9r95ba.css';
import '../../css/g/gc3ocublh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="mc75m8d8n"/><path class="rkf9r95ba"/><path class="gc3ocublh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:image" {...props}></Icon>
