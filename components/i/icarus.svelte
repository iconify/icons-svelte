<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd8hkcb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zd8hkcb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:icarus" {...props}></Icon>
