<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm699vahj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hm699vahj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:archaeopteryx-fossil" {...props}></Icon>
