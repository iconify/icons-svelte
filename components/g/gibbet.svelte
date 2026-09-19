<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw3l-abfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aw3l-abfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gibbet" {...props}></Icon>
