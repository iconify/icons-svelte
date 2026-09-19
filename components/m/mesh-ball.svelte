<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajkmzg0pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajkmzg0pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mesh-ball" {...props}></Icon>
