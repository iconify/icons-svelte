<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhi8lybtb.css';
import '../../css/l/lgjscu5ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhi8lybtb"/><path class="lgjscu5ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-check-big-filled" {...props}></Icon>
