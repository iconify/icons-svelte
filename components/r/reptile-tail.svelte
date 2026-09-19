<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vel8po25y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vel8po25y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:reptile-tail" {...props}></Icon>
