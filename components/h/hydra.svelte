<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmci_qb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmci_qb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hydra" {...props}></Icon>
