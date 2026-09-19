<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd-hzyb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd-hzyb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cheerful" {...props}></Icon>
