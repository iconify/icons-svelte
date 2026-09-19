<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwt473w_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwt473w_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:raining" {...props}></Icon>
