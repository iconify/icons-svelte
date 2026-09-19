<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln14l76-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ln14l76-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clownfish" {...props}></Icon>
