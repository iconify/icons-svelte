<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po_ymlb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="po_ymlb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ropeway" {...props}></Icon>
