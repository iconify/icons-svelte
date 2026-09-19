<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgc-kbc-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgc-kbc-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:platform" {...props}></Icon>
