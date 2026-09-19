<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq8chwoze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aq8chwoze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crystal-ball" {...props}></Icon>
