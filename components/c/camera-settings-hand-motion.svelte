<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy6xpqbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy6xpqbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:camera-settings-hand-motion" {...props}></Icon>
