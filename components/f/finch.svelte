<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euya8fbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="euya8fbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:finch" {...props}></Icon>
