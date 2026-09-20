<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnszzoung.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pnszzoung"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:objects-tree" {...props}></Icon>
