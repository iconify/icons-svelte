<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-ldsdbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-ldsdbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:control-tower" {...props}></Icon>
