<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwktg_e7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwktg_e7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rank-2" {...props}></Icon>
