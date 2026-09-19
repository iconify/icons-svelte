<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q27t-gbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q27t-gbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:river" {...props}></Icon>
