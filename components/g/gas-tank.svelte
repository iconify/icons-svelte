<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufie9ebgy.css';
import '../../css/l/lmzdaxwoj.css';
import '../../css/h/h98i5ybqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ufie9ebgy"><path clip-rule="evenodd" class="lmzdaxwoj"/><path class="h98i5ybqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:gas-tank" {...props}></Icon>
