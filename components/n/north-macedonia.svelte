<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gktr6dbvg.css';
import '../../css/f/fr0bdx4ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="gktr6dbvg"/><path class="fr0bdx4ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:north-macedonia" {...props}></Icon>
