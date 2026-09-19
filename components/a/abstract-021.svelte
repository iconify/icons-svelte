<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3yxocp3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3yxocp3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-021" {...props}></Icon>
