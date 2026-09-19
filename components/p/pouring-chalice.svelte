<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usx2mjb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="usx2mjb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pouring-chalice" {...props}></Icon>
