<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igbd7lb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igbd7lb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flatbed" {...props}></Icon>
