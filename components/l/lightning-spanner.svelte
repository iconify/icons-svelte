<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl3c3ab2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl3c3ab2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-spanner" {...props}></Icon>
