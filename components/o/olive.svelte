<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4d_zkbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4d_zkbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:olive" {...props}></Icon>
