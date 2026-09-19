<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_kis0uyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_kis0uyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:full-wood-bucket-handle" {...props}></Icon>
