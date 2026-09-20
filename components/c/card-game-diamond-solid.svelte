<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx3ex45_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx3ex45_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:card-game-diamond-solid" {...props}></Icon>
