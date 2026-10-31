<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt_lsqbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt_lsqbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hard-drive-gloss" {...props}></Icon>
