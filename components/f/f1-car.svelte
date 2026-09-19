<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9t50-u3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9t50-u3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:f1-car" {...props}></Icon>
