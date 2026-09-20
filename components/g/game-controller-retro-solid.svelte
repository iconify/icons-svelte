<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frs8--b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="frs8--b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:game-controller-retro-solid" {...props}></Icon>
