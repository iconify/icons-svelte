<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3khll-_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3khll-_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:goo-spurt" {...props}></Icon>
