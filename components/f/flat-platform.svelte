<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e01k3n63t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e01k3n63t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flat-platform" {...props}></Icon>
