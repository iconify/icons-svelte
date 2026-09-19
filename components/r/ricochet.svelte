<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf0-_jovq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xf0-_jovq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ricochet" {...props}></Icon>
