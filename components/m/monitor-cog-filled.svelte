<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acoyk8bzs.css';
import '../../css/x/xe4n45bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acoyk8bzs"/><path clip-rule="evenodd" class="xe4n45bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-cog-filled" {...props}></Icon>
