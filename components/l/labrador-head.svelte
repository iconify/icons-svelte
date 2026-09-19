<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe3bh2r2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pe3bh2r2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:labrador-head" {...props}></Icon>
