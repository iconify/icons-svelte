<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg49w7bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jg49w7bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:level-two-advanced" {...props}></Icon>
