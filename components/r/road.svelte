<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqpwwob9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oqpwwob9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:road" {...props}></Icon>
