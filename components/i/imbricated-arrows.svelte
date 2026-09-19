<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o71qcsp3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o71qcsp3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:imbricated-arrows" {...props}></Icon>
