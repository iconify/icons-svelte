<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp7nbbcuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp7nbbcuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:domino-tiles" {...props}></Icon>
