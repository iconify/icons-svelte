<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftgbrob7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftgbrob7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:medieval-barracks" {...props}></Icon>
