<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo5ta_uie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo5ta_uie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plane-wing" {...props}></Icon>
