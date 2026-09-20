<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcgr1exts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcgr1exts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:rock-and-roll-hand-solid" {...props}></Icon>
