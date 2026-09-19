<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdl5jac-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdl5jac-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:machine-gun-magazine" {...props}></Icon>
