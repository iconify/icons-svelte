<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl4beeb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl4beeb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:progression" {...props}></Icon>
