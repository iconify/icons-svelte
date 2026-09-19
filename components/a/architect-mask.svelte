<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-9sqbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc-9sqbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:architect-mask" {...props}></Icon>
