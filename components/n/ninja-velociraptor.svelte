<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2slah9sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2slah9sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ninja-velociraptor" {...props}></Icon>
