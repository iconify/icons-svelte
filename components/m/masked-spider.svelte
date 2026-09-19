<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn3h6pbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nn3h6pbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:masked-spider" {...props}></Icon>
