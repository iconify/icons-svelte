<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tny4cibpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tny4cibpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:purple-tentacle" {...props}></Icon>
