<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1vzvobrg.css';
import '../../css/s/sco2ncz2j.css';
import '../../css/t/tgu2pcaid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1vzvobrg"/><path class="sco2ncz2j"/><path clip-rule="evenodd" class="tgu2pcaid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:card-game-card-spade" {...props}></Icon>
