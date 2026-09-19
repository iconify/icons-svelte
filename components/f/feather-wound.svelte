<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe9t9acdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qe9t9acdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:feather-wound" {...props}></Icon>
