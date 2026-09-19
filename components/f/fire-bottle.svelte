<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fggy_obuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fggy_obuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-bottle" {...props}></Icon>
