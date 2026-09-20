<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpy6qzbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gpy6qzbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:game-controller-retro-outline" {...props}></Icon>
