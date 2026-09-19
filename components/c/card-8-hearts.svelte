<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt95bo9fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kt95bo9fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-8-hearts" {...props}></Icon>
