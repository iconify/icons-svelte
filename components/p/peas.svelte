<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zer6dxb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zer6dxb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:peas" {...props}></Icon>
