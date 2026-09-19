<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doftgs7xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="doftgs7xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:amethyst" {...props}></Icon>
