<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt55pmb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":459,"height":512};
const content = `<path class="pt55pmb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:c-script" {...props}></Icon>
