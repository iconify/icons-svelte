<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4wizrb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4wizrb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bottom-right-3d-arrow" {...props}></Icon>
