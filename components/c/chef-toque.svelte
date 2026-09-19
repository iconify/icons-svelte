<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vug7zdb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vug7zdb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chef-toque" {...props}></Icon>
