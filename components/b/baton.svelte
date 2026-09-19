<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsyd30fdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gsyd30fdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:baton" {...props}></Icon>
