<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlvzy9bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mlvzy9bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:checkbox-tree" {...props}></Icon>
