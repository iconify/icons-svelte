<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3wz1bbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3wz1bbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-shield" {...props}></Icon>
