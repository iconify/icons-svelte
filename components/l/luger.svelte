<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcsid44ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcsid44ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:luger" {...props}></Icon>
