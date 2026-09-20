<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vvvbi4b4n.css';
import '../../css/f/fcamlgh9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vvvbi4b4n"/><path clip-rule="evenodd" class="fcamlgh9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bell-ring-filled" {...props}></Icon>
