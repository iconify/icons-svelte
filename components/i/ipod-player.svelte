<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lekja6r0i.css';
import '../../css/m/mwjzc-b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lekja6r0i"/><path class="mwjzc-b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:ipod-player" {...props}></Icon>
