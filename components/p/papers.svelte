<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx2qpccww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx2qpccww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:papers" {...props}></Icon>
