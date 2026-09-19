<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eray_ub-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eray_ub-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-2-clubs" {...props}></Icon>
