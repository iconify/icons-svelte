<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er6ok1bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="er6ok1bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flaming-sheet" {...props}></Icon>
