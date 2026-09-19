<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3awwsncf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3awwsncf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:muscle-fat" {...props}></Icon>
