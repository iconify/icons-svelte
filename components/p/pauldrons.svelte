<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6l5shx1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6l5shx1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pauldrons" {...props}></Icon>
