<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st6t05p-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="st6t05p-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-6-diamonds" {...props}></Icon>
