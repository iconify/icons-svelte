<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue0vf3bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ue0vf3bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:angel-wings" {...props}></Icon>
