<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z36muvnfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z36muvnfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flying-shuriken" {...props}></Icon>
