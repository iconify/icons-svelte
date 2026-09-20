<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cle0dtw2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cle0dtw2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:reply" {...props}></Icon>
