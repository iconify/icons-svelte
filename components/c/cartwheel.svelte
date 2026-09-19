<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9_082b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9_082b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cartwheel" {...props}></Icon>
