<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3hosabwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3hosabwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:elven-castle" {...props}></Icon>
