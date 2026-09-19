<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_1agk52v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_1agk52v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:multi-directions" {...props}></Icon>
