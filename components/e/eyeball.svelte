<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4g2bi8-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4g2bi8-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eyeball" {...props}></Icon>
