<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6kqlu_fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6kqlu_fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:3d-meeple" {...props}></Icon>
