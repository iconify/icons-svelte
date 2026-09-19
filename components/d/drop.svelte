<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo8-hpbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo8-hpbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:drop" {...props}></Icon>
