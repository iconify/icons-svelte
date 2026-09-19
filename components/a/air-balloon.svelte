<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmlu3limk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmlu3limk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:air-balloon" {...props}></Icon>
