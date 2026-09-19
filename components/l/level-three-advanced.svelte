<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4at3rbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4at3rbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:level-three-advanced" {...props}></Icon>
