<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbzdh2bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tbzdh2bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-plane" {...props}></Icon>
