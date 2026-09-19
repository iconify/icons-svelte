<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqgduybsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqgduybsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:banging-gavel" {...props}></Icon>
