<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z74esbcjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z74esbcjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-pause-fill" {...props}></Icon>
