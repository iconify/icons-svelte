<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn5b7v52d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gn5b7v52d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:key" {...props}></Icon>
