<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1h2e9unp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1h2e9unp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nest-eggs" {...props}></Icon>
