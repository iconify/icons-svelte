<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c81vt37sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c81vt37sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mona-lisa" {...props}></Icon>
