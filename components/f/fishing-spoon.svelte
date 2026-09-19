<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t88s3pb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t88s3pb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fishing-spoon" {...props}></Icon>
