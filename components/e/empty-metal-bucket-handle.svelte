<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp-4tryuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kp-4tryuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:empty-metal-bucket-handle" {...props}></Icon>
