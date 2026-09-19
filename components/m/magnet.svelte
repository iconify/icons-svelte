<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6_f13bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6_f13bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magnet" {...props}></Icon>
