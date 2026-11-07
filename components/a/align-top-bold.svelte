<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nelsscpmr.css';
import '../../css/f/fx2vq-b3e.css';
import '../../css/r/r5hjnw2io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nelsscpmr"/><path class="fx2vq-b3e"/><path class="r5hjnw2io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-top-bold" {...props}></Icon>
