<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqodi2buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqodi2buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mighty-spanner" {...props}></Icon>
