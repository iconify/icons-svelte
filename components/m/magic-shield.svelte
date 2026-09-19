<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2w4e9bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2w4e9bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-shield" {...props}></Icon>
