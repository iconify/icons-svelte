<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvguc5buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvguc5buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:card-game-symbols" {...props}></Icon>
