<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpfw6bb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpfw6bb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:laser-precision" {...props}></Icon>
