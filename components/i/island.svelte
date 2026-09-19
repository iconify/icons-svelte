<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo_1buw-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo_1buw-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:island" {...props}></Icon>
