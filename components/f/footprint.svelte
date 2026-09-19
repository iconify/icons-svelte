<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl7-nrblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gl7-nrblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:footprint" {...props}></Icon>
