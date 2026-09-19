<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v15ynnite.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v15ynnite"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cube" {...props}></Icon>
