<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpbff6b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpbff6b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brazil" {...props}></Icon>
